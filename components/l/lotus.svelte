<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i2qnw-bhf.css';
import '../../css/i/iayt--bmg.css';
import '../../css/v/vvd7iabnl.css';
import '../../css/x/xslfg2evh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="i2qnw-bhf"/><path class="iayt--bmg"/><path class="vvd7iabnl wm-a"/><path class="wm-s xslfg2evh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lotus" {...props}></Icon>
