<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vap1pibst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vap1pibst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:horizontal-align-right" {...props}></Icon>
