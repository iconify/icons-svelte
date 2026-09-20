<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk75-jb2c.css';
import '../../css/b/boxkj20aw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dk75-jb2c"/><path class="boxkj20aw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:external-browser" {...props}></Icon>
