<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx8a74d0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx8a74d0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:package-import" {...props}></Icon>
