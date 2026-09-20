<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwwoteeup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwwoteeup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:monitor-off-sharp" {...props}></Icon>
