<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqq7tyroa.css';
import '../../css/q/q062oc2hv.css';
import '../../css/l/lzkadnb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqq7tyroa"/><path class="q062oc2hv"/><path class="lzkadnb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:panel-bottom" {...props}></Icon>
