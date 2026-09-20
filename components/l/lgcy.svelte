<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcwroccto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcwroccto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lgcy" {...props}></Icon>
