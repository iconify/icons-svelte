<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txy8rw54j.css';
import '../../css/c/cix5zfqeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="txy8rw54j"/><path clip-rule="evenodd" class="cix5zfqeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:clipboard-no-access-solid" {...props}></Icon>
