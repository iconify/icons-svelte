<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4iv2nveq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="z4iv2nveq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:cherries" {...props}></Icon>
