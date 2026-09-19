<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqc3xdbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="gqc3xdbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:contrast" {...props}></Icon>
