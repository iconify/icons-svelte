<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf539cbsg.css';
import '../../css/g/gzff54bpk.css';
import '../../css/u/ucy902b6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<g transform="translate(0 995.638)" class="nf539cbsg"><circle class="gzff54bpk"/><circle class="ucy902b6e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:intermediate-event-non-interrupting" {...props}></Icon>
