<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyt4rsbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyt4rsbar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:phone-x" {...props}></Icon>
