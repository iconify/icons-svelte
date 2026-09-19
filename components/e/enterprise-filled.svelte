<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw9uczfoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw9uczfoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:enterprise-filled" {...props}></Icon>
