<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_auzoz_p.css';
import '../../css/a/a4u_2wblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_auzoz_p"/><path class="a4u_2wblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-crop" {...props}></Icon>
