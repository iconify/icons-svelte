<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/koj8yibyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="koj8yibyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-kick" {...props}></Icon>
