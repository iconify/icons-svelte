<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3apx84gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="n3apx84gf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:krakenjs" {...props}></Icon>
