<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5hha1fvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5hha1fvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:heart" {...props}></Icon>
