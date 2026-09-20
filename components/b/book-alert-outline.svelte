<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7qij3bkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7qij3bkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-alert-outline" {...props}></Icon>
