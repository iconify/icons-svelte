<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi_7mx36a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b pi_7mx36a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:beaker-filled" {...props}></Icon>
