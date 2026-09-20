<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky72wso_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ky72wso_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:expand-diagonal-line" {...props}></Icon>
