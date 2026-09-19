<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r35rppbpm.css';
import '../../css/y/yjyw_obwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r35rppbpm"/><path class="yjyw_obwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:lowerleftfountainpen" {...props}></Icon>
