<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gksx-9i4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":340,"height":512};
const content = `<path class="gksx-9i4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:figma" {...props}></Icon>
