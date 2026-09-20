<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9rdtub8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="i9rdtub8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:jujutsu" {...props}></Icon>
