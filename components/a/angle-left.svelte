<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdjq0irqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdjq0irqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:angle-left" {...props}></Icon>
