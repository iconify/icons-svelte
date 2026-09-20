<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc2aaw2ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vc2aaw2ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:angry" {...props}></Icon>
