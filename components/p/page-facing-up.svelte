<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7g7w1efs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="h7g7w1efs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:page-facing-up" {...props}></Icon>
