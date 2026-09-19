<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru9ga46bg.css';
import '../../css/b/bii6hxbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru9ga46bg"/><path clip-rule="evenodd" class="bii6hxbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:clock" {...props}></Icon>
