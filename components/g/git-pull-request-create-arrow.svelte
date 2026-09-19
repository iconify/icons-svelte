<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp8cm7rty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hp8cm7rty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:git-pull-request-create-arrow" {...props}></Icon>
