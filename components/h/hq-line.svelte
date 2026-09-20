<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9jhqt81o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9jhqt81o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hq-line" {...props}></Icon>
