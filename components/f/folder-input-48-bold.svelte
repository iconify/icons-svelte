<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw19-5bkm.css';
import '../../css/f/fv9h6ebsv.css';
import '../../css/r/r05k69bmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lw19-5bkm"/><path class="fv9h6ebsv"/><path class="r05k69bmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-input-48-bold" {...props}></Icon>
