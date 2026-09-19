<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir9eex94f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ir9eex94f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:nut-fill" {...props}></Icon>
