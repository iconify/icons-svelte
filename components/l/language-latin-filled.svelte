<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1du9-b5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="z1du9-b5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-latin-filled" {...props}></Icon>
