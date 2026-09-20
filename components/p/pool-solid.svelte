<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea-644bal.css';
import '../../css/i/iwz5x-bvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ea-644bal"/><path class="iwz5x-bvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:pool-solid" {...props}></Icon>
