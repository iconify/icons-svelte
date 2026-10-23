<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we0b_qrdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="we0b_qrdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:ribbon" {...props}></Icon>
