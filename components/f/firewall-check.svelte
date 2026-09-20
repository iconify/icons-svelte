<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2kfu7bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2kfu7bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:firewall-check" {...props}></Icon>
