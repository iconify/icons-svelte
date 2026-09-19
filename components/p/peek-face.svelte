<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8l4m88zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="h8l4m88zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:peek-face" {...props}></Icon>
