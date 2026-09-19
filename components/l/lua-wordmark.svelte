<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdnh22bar.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f1vttpb1l.css';
import '../../css/y/y3owh01jo.css';
import '../../css/p/poau05w8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tdnh22bar"/><g class="cuyn6tgcc"><path class="f1vttpb1l"/><path class="y3owh01jo"/></g><path class="poau05w8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:lua-wordmark" {...props}></Icon>
