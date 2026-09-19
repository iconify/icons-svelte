<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k041_p-cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k041_p-cw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:music-filled" {...props}></Icon>
