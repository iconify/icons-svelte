<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/el8ou_bgu.css';
import '../../css/f/fsh7t6b2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="el8ou_bgu"/><path class="fsh7t6b2y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mouse" {...props}></Icon>
