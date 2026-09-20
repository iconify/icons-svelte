<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0_i_4b4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0_i_4b4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:orcid" {...props}></Icon>
