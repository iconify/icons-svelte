<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2sa2gbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m2sa2gbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alarm-add-outline" {...props}></Icon>
