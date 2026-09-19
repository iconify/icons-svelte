<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egtos6b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="egtos6b2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:advantage-circle" {...props}></Icon>
