<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csme_7b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csme_7b1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-down-sm" {...props}></Icon>
