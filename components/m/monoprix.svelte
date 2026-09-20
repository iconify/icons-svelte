<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5mfk_bhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5mfk_bhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:monoprix" {...props}></Icon>
