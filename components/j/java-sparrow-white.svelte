<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na54l-b4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="na54l-b4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:java-sparrow-white" {...props}></Icon>
