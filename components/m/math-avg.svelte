<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3_90pbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3_90pbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:math-avg" {...props}></Icon>
