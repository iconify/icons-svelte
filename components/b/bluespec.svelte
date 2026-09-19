<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3cou9bya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":402,"height":512};
const content = `<path class="e3cou9bya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:bluespec" {...props}></Icon>
