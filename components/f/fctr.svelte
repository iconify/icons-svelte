<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_qag_boy.css';
import '../../css/i/ik464kqyv.css';
import '../../css/o/okefe65_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_qag_boy"/><path class="ik464kqyv"/><path class="okefe65_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fctr" {...props}></Icon>
