<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ousr7gb-s.css';
import '../../css/s/s7at75-qv.css';
import '../../css/d/dz1d2ub-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ousr7gb-s wm-k"/><path class="s7at75-qv wm-k"/><path class="dz1d2ub-o wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:panel-left-open" {...props}></Icon>
