<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-5919gss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="b-5919gss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:rocket-compact" {...props}></Icon>
