<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7t_4ffnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7t_4ffnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:google-photos-logo" {...props}></Icon>
