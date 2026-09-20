<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyioyxu9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyioyxu9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:adobe-alt" {...props}></Icon>
