<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo94e-b0r.css';
import '../../css/e/enjmbiu9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo94e-b0r"/><path class="enjmbiu9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:pro" {...props}></Icon>
