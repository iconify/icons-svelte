<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwhcp7rhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="mwhcp7rhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:propeller-3" {...props}></Icon>
