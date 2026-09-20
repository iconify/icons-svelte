<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdydk6bsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="bdydk6bsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:erlang" {...props}></Icon>
