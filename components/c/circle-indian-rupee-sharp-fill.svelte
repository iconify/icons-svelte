<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwjl2vbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wwjl2vbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-indian-rupee-sharp-fill" {...props}></Icon>
