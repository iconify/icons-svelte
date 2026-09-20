<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f65x4gbxw.css';
import '../../css/w/w1jc-qglq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f65x4gbxw"/><path class="w1jc-qglq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:inbox" {...props}></Icon>
