<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c54t2hbrn.css';
import '../../css/j/jvp9h3b4s.css';
import '../../css/g/g3r25me4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c54t2hbrn"/><path class="jvp9h3b4s"/><path clip-rule="evenodd" class="g3r25me4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:npxs" {...props}></Icon>
