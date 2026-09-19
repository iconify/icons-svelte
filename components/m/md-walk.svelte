<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gggi5_ica.css';
import '../../css/o/o_oa07brn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gggi5_ica"/><path class="o_oa07brn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-walk" {...props}></Icon>
