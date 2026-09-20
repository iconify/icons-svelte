<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zht8thbji.css';
import '../../css/q/qb4cy_fkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zht8thbji"/><path class="qb4cy_fkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:clone" {...props}></Icon>
