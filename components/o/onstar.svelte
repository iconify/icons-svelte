<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrhy5acrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrhy5acrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:onstar" {...props}></Icon>
