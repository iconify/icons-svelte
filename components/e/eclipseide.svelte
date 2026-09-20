<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxyxrmn-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxyxrmn-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:eclipseide" {...props}></Icon>
