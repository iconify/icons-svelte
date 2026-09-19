<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwzh_rbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fwzh_rbyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:checkbox-composite-reversed" {...props}></Icon>
