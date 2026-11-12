<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1-d8oozv.css';
import '../../css/m/mas9rozrn.css';
import '../../css/i/i49k2acdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j1-d8oozv"/><path class="mas9rozrn"/><path class="i49k2acdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:onlyoffice-light" {...props}></Icon>
