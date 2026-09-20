<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozo9kkyme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1080,"height":1080};
const content = `<path class="ozo9kkyme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:evidence-dev" {...props}></Icon>
