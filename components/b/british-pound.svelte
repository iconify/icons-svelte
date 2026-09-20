<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akze_okwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="akze_okwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:british-pound" {...props}></Icon>
