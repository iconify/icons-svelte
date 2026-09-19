<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw5ds4b9n.css';
import '../../css/r/r6--z6kjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="lw5ds4b9n"/><path class="r6--z6kjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:male-outline" {...props}></Icon>
