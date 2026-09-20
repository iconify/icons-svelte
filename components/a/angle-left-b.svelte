<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvm0pk2cj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvm0pk2cj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:angle-left-b" {...props}></Icon>
