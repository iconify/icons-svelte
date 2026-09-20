<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/q/qoh9i_b1g.css';
import '../../css/h/ham1s0bpn.css';
import '../../css/c/cdbmygnqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="qoh9i_b1g"/><path class="ham1s0bpn"/><path class="cdbmygnqf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:notes-quill" {...props}></Icon>
