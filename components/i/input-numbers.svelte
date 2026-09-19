<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyzek-p_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="fyzek-p_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:input-numbers" {...props}></Icon>
