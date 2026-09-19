<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5cgbab2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":614};
const content = `<path class="g5cgbab2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:keyboard" {...props}></Icon>
