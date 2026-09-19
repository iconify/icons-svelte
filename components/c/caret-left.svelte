<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp3yqspdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":1280};
const content = `<path class="fp3yqspdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:caret-left" {...props}></Icon>
