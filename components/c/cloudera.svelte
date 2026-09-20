<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv19_epck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fv19_epck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:cloudera" {...props}></Icon>
