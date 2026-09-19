<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvyw8shky.css';
import '../../css/s/si38sl8xh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvyw8shky"/><path class="si38sl8xh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:church" {...props}></Icon>
