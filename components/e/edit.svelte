<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bro3b7b7u.css';
import '../../css/p/ptu48kbob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bro3b7b7u"/><path class="ptu48kbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:edit" {...props}></Icon>
