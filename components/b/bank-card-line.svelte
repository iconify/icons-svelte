<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve2j52bfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ve2j52bfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bank-card-line" {...props}></Icon>
