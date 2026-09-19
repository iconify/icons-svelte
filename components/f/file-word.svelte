<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja9avj50u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ja9avj50u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:file-word" {...props}></Icon>
