<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awxwfdbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awxwfdbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:magnifying-glass-plus" {...props}></Icon>
