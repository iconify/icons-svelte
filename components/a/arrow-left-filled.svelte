<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia4xzzwuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ia4xzzwuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-left-filled" {...props}></Icon>
