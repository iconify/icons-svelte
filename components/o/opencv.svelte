<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjxsglbxd.css';
import '../../css/b/bmmii1ffg.css';
import '../../css/i/izbfus17g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="cjxsglbxd"/><path class="bmmii1ffg"/><path class="izbfus17g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:opencv" {...props}></Icon>
