<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfhr38b4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfhr38b4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:eight-sleep" {...props}></Icon>
