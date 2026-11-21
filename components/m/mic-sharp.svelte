<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxqbwqxaq.css';
import '../../css/a/a-5p04cix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cxqbwqxaq"/><path class="a-5p04cix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:mic-sharp" {...props}></Icon>
