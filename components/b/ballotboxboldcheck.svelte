<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m640zw-kt.css';
import '../../css/h/h4318abpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m640zw-kt"/><path class="h4318abpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:ballotboxboldcheck" {...props}></Icon>
