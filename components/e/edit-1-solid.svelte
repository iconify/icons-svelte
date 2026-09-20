<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q882dvb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q882dvb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:edit-1-solid" {...props}></Icon>
