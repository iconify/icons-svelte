<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2rng6b4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y2rng6b4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:dice-6" {...props}></Icon>
