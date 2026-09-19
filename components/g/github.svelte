<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h18a-pf2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="h18a-pf2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:github" {...props}></Icon>
