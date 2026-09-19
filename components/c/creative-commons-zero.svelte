<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2qj_dbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="s2qj_dbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:creative-commons-zero" {...props}></Icon>
