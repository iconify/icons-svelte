<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag4uoqbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ag4uoqbgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:paint-bucket-drop-16" {...props}></Icon>
