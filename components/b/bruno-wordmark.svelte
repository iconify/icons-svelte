<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyke8k9iy.css';
import '../../css/n/ng0hn9-bg.css';
import '../../css/b/b9xf7m9kb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hyke8k9iy"/><path class="ng0hn9-bg"/><path class="b9xf7m9kb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:bruno-wordmark" {...props}></Icon>
