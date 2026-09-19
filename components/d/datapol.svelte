<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfth-yblq.css';
import '../../css/y/yzsp5cclf.css';
import '../../css/u/u6upu__6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfth-yblq"/><path class="yzsp5cclf"/><path class="u6upu__6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:datapol" {...props}></Icon>
