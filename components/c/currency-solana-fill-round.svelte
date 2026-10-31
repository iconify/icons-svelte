<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1a2jjbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1a2jjbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:currency-solana-fill-round" {...props}></Icon>
