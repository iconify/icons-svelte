<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/j/jln0xabaj.css';
import '../../css/l/l564diblt.css';
import '../../css/q/qddlig8lw.css';
import '../../css/z/z8ghr5htt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="jln0xabaj wm-shadow"/><path class="l564diblt wm-shadow"/><path class="qddlig8lw"/><path class="z8ghr5htt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:avatar-tiger" {...props}></Icon>
