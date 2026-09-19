<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miewjjykf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="miewjjykf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:cc-jcb" {...props}></Icon>
