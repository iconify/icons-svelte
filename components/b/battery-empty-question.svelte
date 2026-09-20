<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehjrp2gbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ehjrp2gbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:battery-empty-question" {...props}></Icon>
