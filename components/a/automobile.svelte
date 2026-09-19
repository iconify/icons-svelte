<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxwcq69ty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="fxwcq69ty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:automobile" {...props}></Icon>
