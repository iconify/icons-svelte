<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd8yle12b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1888,"height":1408};
const content = `<path class="pd8yle12b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:folder-open" {...props}></Icon>
