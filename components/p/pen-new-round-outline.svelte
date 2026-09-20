<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo_qq2bqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uo_qq2bqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pen-new-round-outline" {...props}></Icon>
