<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rogyzp3fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":928,"height":1408};
const content = `<path class="rogyzp3fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:inr" {...props}></Icon>
