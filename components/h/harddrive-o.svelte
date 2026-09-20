<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8rxm1btm.css';
import '../../css/j/ji5_h82hg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b8rxm1btm"/><path class="ji5_h82hg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:harddrive-o" {...props}></Icon>
