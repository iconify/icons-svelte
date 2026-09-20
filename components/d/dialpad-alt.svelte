<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubwaw7-jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubwaw7-jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:dialpad-alt" {...props}></Icon>
