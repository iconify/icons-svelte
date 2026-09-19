<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwq9oyboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jwq9oyboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:folder-circle-fill" {...props}></Icon>
