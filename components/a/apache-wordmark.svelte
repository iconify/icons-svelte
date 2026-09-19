<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc41zybcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="sc41zybcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:apache-wordmark" {...props}></Icon>
