<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm2t39b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1280};
const content = `<path class="cm2t39b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:hdd-o" {...props}></Icon>
