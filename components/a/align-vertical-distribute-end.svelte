<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/koyvn77_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="koyvn77_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-vertical-distribute-end" {...props}></Icon>
