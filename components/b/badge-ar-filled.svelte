<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wngwu12gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wngwu12gm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:badge-ar-filled" {...props}></Icon>
