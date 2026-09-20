<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el_l0sbow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="el_l0sbow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-adobe-lightroom-filled" {...props}></Icon>
