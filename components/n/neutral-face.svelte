<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4hb1cc6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="o4hb1cc6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:neutral-face" {...props}></Icon>
