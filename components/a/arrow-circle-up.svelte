<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxsoy8glv.css';
import '../../css/q/q098jibdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxsoy8glv"/><path class="q098jibdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:arrow-circle-up" {...props}></Icon>
