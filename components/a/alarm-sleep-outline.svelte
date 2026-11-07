<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzp1lwttm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bzp1lwttm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alarm-sleep-outline" {...props}></Icon>
