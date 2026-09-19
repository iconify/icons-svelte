<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm581lbny.css';
import '../../css/v/v7vmxtb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="fm581lbny"/><path class="v7vmxtb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:illustrator" {...props}></Icon>
