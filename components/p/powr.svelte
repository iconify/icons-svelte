<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlih9fbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nlih9fbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:powr" {...props}></Icon>
