<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn8ox-tri.css';
import '../../css/d/dqshq-b0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="rn8ox-tri"/><path class="dqshq-b0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:easy-redmine" {...props}></Icon>
