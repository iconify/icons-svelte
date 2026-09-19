<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvfl6rbyb.css';
import '../../css/i/iu8u25bgh.css';
import '../../css/c/cvkuub02k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="lvfl6rbyb"/><path class="iu8u25bgh"/><path class="cvkuub02k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:git-wordmark" {...props}></Icon>
