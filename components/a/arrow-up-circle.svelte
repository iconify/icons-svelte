<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tny2aw3uc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tny2aw3uc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-up-circle" {...props}></Icon>
