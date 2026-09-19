<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hec1o9hrf.css';
import '../../css/a/ablh-jbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hec1o9hrf"/><path class="ablh-jbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:cloud-run-for-anthos" {...props}></Icon>
