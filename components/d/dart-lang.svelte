<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwi71uu0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="dwi71uu0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:dart-lang" {...props}></Icon>
