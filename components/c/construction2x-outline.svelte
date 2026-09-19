<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvev64bnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="uvev64bnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:construction2x-outline" {...props}></Icon>
