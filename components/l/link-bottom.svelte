<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2_iq0bed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2_iq0bed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:link-bottom" {...props}></Icon>
