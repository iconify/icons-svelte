<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8b-1acnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":704};
const content = `<path class="t8b-1acnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:helicopter" {...props}></Icon>
