<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trnzyybym.css';
import '../../css/s/shqj82b5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="trnzyybym"/><path class="shqj82b5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:keyword-16" {...props}></Icon>
