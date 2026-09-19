<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7lf6sb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="s7lf6sb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:pinterest" {...props}></Icon>
