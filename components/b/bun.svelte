<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osbm_yzxy.css';
import '../../css/a/ay6sfyn6f.css';
import '../../css/p/pwf6_mkij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osbm_yzxy"/><path class="ay6sfyn6f"/><path class="pwf6_mkij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:bun" {...props}></Icon>
