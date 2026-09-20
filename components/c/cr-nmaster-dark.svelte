<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j36ek5mfl.css';
import '../../css/w/wyq4150dw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j36ek5mfl"/><path class="wyq4150dw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cr-nmaster-dark" {...props}></Icon>
