<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk-6hydha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="sk-6hydha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:reverse-alt" {...props}></Icon>
