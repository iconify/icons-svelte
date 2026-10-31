<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/o/o9116fb6p.css';
import '../../css/o/o7es60yyc.css';
import '../../css/g/gvv2ijfji.css';
import '../../css/s/s9232rcgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="o9116fb6p wm-shadow"/><path class="o7es60yyc"/><path class="gvv2ijfji"/><path class="s9232rcgp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-retro:avatar-person-wheelchair" {...props}></Icon>
