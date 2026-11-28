<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/j5qqge4bo.css';
import '../../css/u/uppxbxbjq.css';
import '../../css/x/xeziup3uu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="j5qqge4bo"/><path class="uppxbxbjq"/><path class="xeziup3uu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:asterisk-duo" {...props}></Icon>
