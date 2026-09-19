<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj-kozb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj-kozb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:horizontal-distribute-center-filled" {...props}></Icon>
