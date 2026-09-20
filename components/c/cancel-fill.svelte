<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx8su-bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zx8su-bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:cancel-fill" {...props}></Icon>
