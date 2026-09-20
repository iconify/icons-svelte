<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayp-n_9at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ayp-n_9at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:page-setting-remix" {...props}></Icon>
