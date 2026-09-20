<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhi_7zbfl.css';
import '../../css/m/mjirkcbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhi_7zbfl"/><path class="mjirkcbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:browse-filled" {...props}></Icon>
