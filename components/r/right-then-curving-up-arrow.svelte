<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shjrjgzhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="shjrjgzhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:right-then-curving-up-arrow" {...props}></Icon>
