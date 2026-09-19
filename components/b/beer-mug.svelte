<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9sd74bbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="z9sd74bbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:beer-mug" {...props}></Icon>
