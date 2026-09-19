<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny8b-ebnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ny8b-ebnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:next" {...props}></Icon>
