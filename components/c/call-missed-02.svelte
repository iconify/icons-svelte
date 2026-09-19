<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d52muybuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d52muybuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:call-missed-02" {...props}></Icon>
