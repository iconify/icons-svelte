<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds1hiib0s.css';
import '../../css/q/qth2s3b6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ds1hiib0s"/><path class="qth2s3b6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-subject" {...props}></Icon>
