<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq9mvibxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mq9mvibxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:home-2-bold" {...props}></Icon>
