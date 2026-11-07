<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg3heibao.css';
import '../../css/i/i9yzznx8e.css';
import '../../css/t/t1r1agbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pg3heibao"/><path class="i9yzznx8e"/><path class="t1r1agbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-smile-bold-duotone" {...props}></Icon>
