<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjxey5bjp.css';
import '../../css/h/hgf0v-b3k.css';
import '../../css/c/cm-f3t2vn.css';
import '../../css/d/dyuvwzb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vjxey5bjp"/><circle class="hgf0v-b3k"/><path class="cm-f3t2vn"/><path class="dyuvwzb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:pytorch-wordmark" {...props}></Icon>
