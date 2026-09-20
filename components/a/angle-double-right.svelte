<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ial6mtbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ial6mtbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:angle-double-right" {...props}></Icon>
