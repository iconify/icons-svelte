<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4vayl4jb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="o4vayl4jb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cloud-fog" {...props}></Icon>
