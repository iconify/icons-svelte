<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arzliyesj.css';
import '../../css/j/jjrjjnjfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="arzliyesj"/><path class="jjrjjnjfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:development" {...props}></Icon>
