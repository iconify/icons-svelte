<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bijlm4yyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bijlm4yyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:microsoft-xbox-controller-battery-charging" {...props}></Icon>
