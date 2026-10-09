<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajbt87aul.css';
import '../../css/b/bjh1ltbve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ajbt87aul"/><path class="bjh1ltbve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lockbox-20-bold" {...props}></Icon>
