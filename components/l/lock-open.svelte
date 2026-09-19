<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj90n0u7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xj90n0u7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:lock-open" {...props}></Icon>
