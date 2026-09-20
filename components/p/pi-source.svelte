<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stc4fdcup.css';
import '../../css/k/k370xsb9r.css';
import '../../css/h/hdfgeqb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="stc4fdcup"/><path class="k370xsb9r"/><path class="hdfgeqb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pi-source" {...props}></Icon>
