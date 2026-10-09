<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6z7-hvpd.css';
import '../../css/m/ms-gp00fr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a6z7-hvpd"/><path class="ms-gp00fr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cooling-tower-20-bold" {...props}></Icon>
