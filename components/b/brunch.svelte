<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gknx1g06q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gknx1g06q st0"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:brunch" {...props}></Icon>
