<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bprebx11j.css';
import '../../css/o/ofznhc5pn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bprebx11j"/><path class="ofznhc5pn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:control-panel-20-bold" {...props}></Icon>
