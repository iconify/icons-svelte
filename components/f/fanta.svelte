<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfbnxnbud.css';
import '../../css/l/l7jujabhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":224.99,"height":160.66};
const content = `<path class="hfbnxnbud"/><path class="l7jujabhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fanta" {...props}></Icon>
