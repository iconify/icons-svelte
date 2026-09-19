<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr9z3j45u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kr9z3j45u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:bowling-ball" {...props}></Icon>
