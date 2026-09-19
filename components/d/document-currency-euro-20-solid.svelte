<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihqw2pbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ihqw2pbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-currency-euro-20-solid" {...props}></Icon>
