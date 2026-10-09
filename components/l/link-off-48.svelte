<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he122gpwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="he122gpwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:link-off-48" {...props}></Icon>
