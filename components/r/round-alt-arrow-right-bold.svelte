<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_mqttbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e_mqttbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-alt-arrow-right-bold" {...props}></Icon>
