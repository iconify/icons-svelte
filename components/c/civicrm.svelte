<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4bmut06u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z4bmut06u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:civicrm" {...props}></Icon>
