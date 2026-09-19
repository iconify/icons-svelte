<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah-h2x4ww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ah-h2x4ww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:phoenix-framework" {...props}></Icon>
