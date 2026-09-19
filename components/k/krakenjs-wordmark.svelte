<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugqf5ebaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ugqf5ebaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:krakenjs-wordmark" {...props}></Icon>
