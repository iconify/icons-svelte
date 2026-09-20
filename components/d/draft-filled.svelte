<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js71uubxl.css';
import '../../css/g/gwy33kf_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="js71uubxl"/><path class="gwy33kf_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:draft-filled" {...props}></Icon>
