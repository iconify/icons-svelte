<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3rm31rhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="k3rm31rhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:file-lines" {...props}></Icon>
