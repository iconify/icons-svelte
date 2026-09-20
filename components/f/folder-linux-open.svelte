<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov4w-vcsn.css';
import '../../css/g/gs0gqsb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ov4w-vcsn"/><path class="gs0gqsb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-linux-open" {...props}></Icon>
