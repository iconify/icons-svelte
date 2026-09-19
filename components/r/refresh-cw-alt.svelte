<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kysr_vuyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kysr_vuyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:refresh-cw-alt" {...props}></Icon>
