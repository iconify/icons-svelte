<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_b2hwbyf.css';
import '../../css/o/oj5wobigx.css';
import '../../css/r/r5bozrdyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_b2hwbyf"/><path class="oj5wobigx"/><path class="r5bozrdyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:hospital" {...props}></Icon>
