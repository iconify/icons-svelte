<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5pd5bcbi.css';
import '../../css/q/q33pllwot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5pd5bcbi"/><path class="q33pllwot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:border-outer-filled" {...props}></Icon>
