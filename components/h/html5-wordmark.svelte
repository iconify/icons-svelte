<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8p978b8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="o8p978b8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:html5-wordmark" {...props}></Icon>
