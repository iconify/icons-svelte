<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkjpidb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="nkjpidb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-hira" {...props}></Icon>
