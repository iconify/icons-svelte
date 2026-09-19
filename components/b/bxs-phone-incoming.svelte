<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvbubjb1v.css';
import '../../css/p/pj85_iwji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jvbubjb1v"/><path class="pj85_iwji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-phone-incoming" {...props}></Icon>
