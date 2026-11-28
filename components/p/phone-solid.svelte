<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bypk2g5eg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bypk2g5eg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:phone-solid" {...props}></Icon>
