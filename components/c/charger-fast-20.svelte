<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr0clkknd.css';
import '../../css/n/nevhvhrth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zr0clkknd"/><path class="nevhvhrth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charger-fast-20" {...props}></Icon>
