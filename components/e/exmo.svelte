<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs3rl09dx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xs3rl09dx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:exmo" {...props}></Icon>
