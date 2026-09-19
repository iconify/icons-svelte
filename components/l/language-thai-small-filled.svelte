<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/texobfhvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="texobfhvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-thai-small-filled" {...props}></Icon>
