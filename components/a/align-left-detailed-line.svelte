<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z49j_bcoz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z49j_bcoz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-left-detailed-line" {...props}></Icon>
