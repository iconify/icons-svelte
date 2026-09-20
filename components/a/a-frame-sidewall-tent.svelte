<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqh81ubec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jqh81ubec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:a-frame-sidewall-tent" {...props}></Icon>
