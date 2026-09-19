<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v39fq-b_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v39fq-b_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:maze" {...props}></Icon>
