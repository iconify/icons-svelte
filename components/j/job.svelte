<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdcnc9bhs.css';
import '../../css/x/xi2u7tbob.css';
import '../../css/i/i2y_m2scu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18.035,"height":17.5};
const content = `<path class="rdcnc9bhs"/><path class="xi2u7tbob"/><path class="i2y_m2scu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="k8s:job" {...props}></Icon>
