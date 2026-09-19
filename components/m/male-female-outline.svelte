<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmzvefsak.css';
import '../../css/v/v68l-3b8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="zmzvefsak"/><path class="v68l-3b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:male-female-outline" {...props}></Icon>
