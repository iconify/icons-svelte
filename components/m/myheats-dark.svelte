<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh__4bxtl.css';
import '../../css/r/r1xemmb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oh__4bxtl"/><path class="r1xemmb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:myheats-dark" {...props}></Icon>
