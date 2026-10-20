<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdcnc9bhs.css';
import '../../css/x/xi2u7tbob.css';
import '../../css/w/wuc6jt4fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18.035,"height":17.5};
const content = `<path class="rdcnc9bhs"/><path class="xi2u7tbob"/><path class="wuc6jt4fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="k8s:namespace" {...props}></Icon>
