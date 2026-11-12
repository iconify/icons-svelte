<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks3m9vbsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks3m9vbsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:building-pin" {...props}></Icon>
