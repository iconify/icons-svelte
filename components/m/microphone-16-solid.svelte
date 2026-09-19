<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1mnhwjrl.css';
import '../../css/a/a311pob4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g1mnhwjrl"/><path class="a311pob4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:microphone-16-solid" {...props}></Icon>
