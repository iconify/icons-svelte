<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqj-t9lbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hqj-t9lbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pickaxe" {...props}></Icon>
