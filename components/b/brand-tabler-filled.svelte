<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrqn8np3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrqn8np3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-tabler-filled" {...props}></Icon>
