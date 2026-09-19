<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kci5s6b3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":441,"height":512};
const content = `<path class="kci5s6b3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:dragonflybsd" {...props}></Icon>
