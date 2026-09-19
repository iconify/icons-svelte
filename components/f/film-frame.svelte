<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv7f0q5lo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="iv7f0q5lo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:film-frame" {...props}></Icon>
