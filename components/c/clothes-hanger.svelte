<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaml5tb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oaml5tb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:clothes-hanger" {...props}></Icon>
