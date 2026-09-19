<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v16dgddoa.css';
import '../../css/y/y4nobsbrk.css';
import '../../css/z/ziavmd8sc.css';
import '../../css/k/kp1357raw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="v16dgddoa"/><path class="y4nobsbrk"/><path class="ziavmd8sc"/><path class="kp1357raw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:radio-sharp" {...props}></Icon>
