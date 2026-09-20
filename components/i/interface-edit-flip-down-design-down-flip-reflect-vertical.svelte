<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fga303buv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="fga303buv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-edit-flip-down-design-down-flip-reflect-vertical" {...props}></Icon>
