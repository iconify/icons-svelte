<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozz-8wjpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="ozz-8wjpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:linear-wordmark" {...props}></Icon>
