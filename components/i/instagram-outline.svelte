<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be-x2lgok.css';
import '../../css/j/j0991s5ot.css';
import '../../css/d/daxtkab1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="be-x2lgok"/><path clip-rule="evenodd" class="j0991s5ot"/><path clip-rule="evenodd" class="daxtkab1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:instagram-outline" {...props}></Icon>
