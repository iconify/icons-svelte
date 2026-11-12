<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3jkgcbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="b3jkgcbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:aerospace" {...props}></Icon>
