<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwia4_b9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="jwia4_b9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-two" {...props}></Icon>
