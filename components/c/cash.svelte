<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozrfghbao.css';
import '../../css/h/h7g0yix5d.css';
import '../../css/v/v1jjnr7lu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ozrfghbao"/><path class="h7g0yix5d"/><path class="v1jjnr7lu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:cash" {...props}></Icon>
