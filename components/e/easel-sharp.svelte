<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyy3z6b2h.css';
import '../../css/b/b0bieq5rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jyy3z6b2h"/><path class="b0bieq5rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:easel-sharp" {...props}></Icon>
