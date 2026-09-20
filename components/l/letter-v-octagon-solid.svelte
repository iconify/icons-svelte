<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_0em7blx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_0em7blx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-v-octagon-solid" {...props}></Icon>
