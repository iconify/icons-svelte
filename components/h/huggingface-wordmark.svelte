<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnojpx50x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="mnojpx50x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:huggingface-wordmark" {...props}></Icon>
