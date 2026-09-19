<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgkwoabeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="pgkwoabeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-thai-small" {...props}></Icon>
