<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdcnc9bhs.css';
import '../../css/x/xi2u7tbob.css';
import '../../css/r/rs176bbpc.css';
import '../../css/i/ihrg4ygup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18.035,"height":17.5};
const content = `<path class="rdcnc9bhs"/><path class="xi2u7tbob"/><path class="rs176bbpc"/><path class="ihrg4ygup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="k8s:deployment" {...props}></Icon>
