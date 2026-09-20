<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xgs6gwb0y.css';
import '../../css/o/o5uaqla1a.css';
import '../../css/y/yns7dfelz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xgs6gwb0y"/><path class="o5uaqla1a"/><path class="yns7dfelz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mail" {...props}></Icon>
