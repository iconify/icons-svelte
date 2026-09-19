<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilw5bac2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ilw5bac2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:kubernetes" {...props}></Icon>
