<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u2398wb7u.css';
import '../../css/s/s76kbrb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":44,"height":44};
const content = `<g class="ft5dv1b6b"><rect class="u2398wb7u"/><path class="s76kbrb9m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ahooks" {...props}></Icon>
