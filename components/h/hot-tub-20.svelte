<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yeyvl7vpf.css';
import '../../css/w/wzh_nvbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yeyvl7vpf"/><path class="wzh_nvbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hot-tub-20" {...props}></Icon>
