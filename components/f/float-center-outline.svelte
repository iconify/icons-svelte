<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wph-eob-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wph-eob-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:float-center-outline" {...props}></Icon>
