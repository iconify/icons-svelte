<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at62glbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="at62glbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:paint-roll-brush-16" {...props}></Icon>
