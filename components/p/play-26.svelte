<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylnr7y52n.css';
import '../../css/h/hs-lm0b_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<circle class="ylnr7y52n"/><path class="hs-lm0b_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:play-26" {...props}></Icon>
