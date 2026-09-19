<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we144-bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="we144-bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:agent" {...props}></Icon>
