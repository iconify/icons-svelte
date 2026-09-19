<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzevmeb7i.css';
import '../../css/q/q2sfcejqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pzevmeb7i"/><path class="q2sfcejqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:inbox-arrow-down-16-solid" {...props}></Icon>
