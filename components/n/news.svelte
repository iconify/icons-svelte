<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1ufupj8t.css';
import '../../css/b/bfqat1bhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1ufupj8t"/><path class="bfqat1bhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:news" {...props}></Icon>
