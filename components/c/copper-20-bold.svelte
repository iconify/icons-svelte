<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkwxxqb3q.css';
import '../../css/f/f6w9iq-hg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kkwxxqb3q"/><path class="f6w9iq-hg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:copper-20-bold" {...props}></Icon>
