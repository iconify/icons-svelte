<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh1vn_bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fh1vn_bxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:php" {...props}></Icon>
