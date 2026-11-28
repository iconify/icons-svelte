<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4nqr853o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4nqr853o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:app-window-plus" {...props}></Icon>
