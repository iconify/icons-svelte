<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nstk77byy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="nstk77byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:kaggle" {...props}></Icon>
