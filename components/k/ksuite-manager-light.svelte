<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy8rokwbh.css';
import '../../css/e/eajtpz02m.css';
import '../../css/q/qxwq8bcbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jy8rokwbh"/><path class="eajtpz02m"/><path class="qxwq8bcbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-manager-light" {...props}></Icon>
