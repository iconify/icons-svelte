<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfcmei0vg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dfcmei0vg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:landline" {...props}></Icon>
