<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nggtlqu-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":718,"height":701};
const content = `<path class="nggtlqu-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:clip" {...props}></Icon>
