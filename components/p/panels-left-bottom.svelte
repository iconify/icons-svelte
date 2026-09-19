<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpcjsnqpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpcjsnqpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:panels-left-bottom" {...props}></Icon>
