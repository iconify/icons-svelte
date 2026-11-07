<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb1na5jao.css';
import '../../css/z/z7rhdcbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bb1na5jao"/><path clip-rule="evenodd" class="z7rhdcbxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:double-alt-arrow-up-bold-duotone" {...props}></Icon>
