<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvcanoprh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="bvcanoprh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:adobe-illustrator" {...props}></Icon>
