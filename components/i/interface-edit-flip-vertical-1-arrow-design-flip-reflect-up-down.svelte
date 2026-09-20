<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/silnjob3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="silnjob3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-edit-flip-vertical-1-arrow-design-flip-reflect-up-down" {...props}></Icon>
