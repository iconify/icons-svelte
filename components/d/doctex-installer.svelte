<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbvmo8dlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hbvmo8dlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:doctex-installer" {...props}></Icon>
