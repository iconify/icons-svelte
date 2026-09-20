<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/banko5b2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="banko5b2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:playlist" {...props}></Icon>
