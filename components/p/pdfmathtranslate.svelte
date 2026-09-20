<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clrj_mvqf.css';
import '../../css/a/ay6n8vh9w.css';
import '../../css/v/v2bqu0buz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="clrj_mvqf"/><path class="ay6n8vh9w"/><path class="v2bqu0buz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pdfmathtranslate" {...props}></Icon>
