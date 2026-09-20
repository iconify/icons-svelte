<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1rmevb5d.css';
import '../../css/s/sa9ni4pvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w1rmevb5d"/><path class="sa9ni4pvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:newspaper" {...props}></Icon>
