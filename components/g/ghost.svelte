<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af5y71jug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="af5y71jug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:ghost" {...props}></Icon>
