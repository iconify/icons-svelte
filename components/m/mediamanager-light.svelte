<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf5ax2rgf.css';
import '../../css/r/r39nnteoa.css';
import '../../css/e/eog225bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rf5ax2rgf"/><path class="r39nnteoa"/><path class="eog225bus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mediamanager-light" {...props}></Icon>
