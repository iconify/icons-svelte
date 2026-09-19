<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofnqojbtj.css';
import '../../css/n/nrfjz124s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ofnqojbtj"/><path class="nrfjz124s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nodemon" {...props}></Icon>
