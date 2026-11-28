<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx-3qfb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sx-3qfb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clipboard-list-plus" {...props}></Icon>
