<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufe16c4_h.css';
import '../../css/c/cnog61bgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ufe16c4_h"/><path class="cnog61bgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:dialogflow" {...props}></Icon>
