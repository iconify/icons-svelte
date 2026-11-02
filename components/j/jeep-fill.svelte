<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-a60zbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-a60zbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:jeep-fill" {...props}></Icon>
