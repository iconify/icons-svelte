<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/styz6ccuf.css';
import '../../css/u/uiueq6bgh.css';
import '../../css/h/hbr51igjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="styz6ccuf"/><path class="uiueq6bgh"/><path class="hbr51igjp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:bed-light" {...props}></Icon>
