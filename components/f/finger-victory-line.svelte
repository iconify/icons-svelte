<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra3zzfhcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ra3zzfhcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:finger-victory-line" {...props}></Icon>
