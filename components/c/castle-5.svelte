<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/ht3awmbjv.css';
import '../../css/q/qk2k3fbxw.css';
import '../../css/y/yi4d1dclt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ht3awmbjv"/><path class="qk2k3fbxw"/><path class="yi4d1dclt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:castle-5" {...props}></Icon>
