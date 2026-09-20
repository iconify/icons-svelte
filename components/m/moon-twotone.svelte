<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmt9bv.css';
import '../../css/y/ydovum.css';
import '../../css/c/cg7sdy.css';
import '../../css/b/b5dely.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-56.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/f/fade-to-1.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmt9bv ydovum"/><path class="cg7sdy ydovum"/><path class="b5dely ydovum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:moon-twotone" {...props}></Icon>
