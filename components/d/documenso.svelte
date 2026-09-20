<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe2_ycbjb.css';
import '../../css/f/ft_gti1us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xe2_ycbjb"/><path class="ft_gti1us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:documenso" {...props}></Icon>
