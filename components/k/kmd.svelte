<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfy-5hqci.css';
import '../../css/x/x0u_kcboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfy-5hqci"/><path class="x0u_kcboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kmd" {...props}></Icon>
