<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_r5o2bnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_r5o2bnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:lock-open-password-solid" {...props}></Icon>
