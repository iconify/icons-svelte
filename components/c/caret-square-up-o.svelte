<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cflr1ab0i.css';
import '../../css/z/zi_-u-bqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cflr1ab0i"/><path class="zi_-u-bqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:caret-square-up-o" {...props}></Icon>
