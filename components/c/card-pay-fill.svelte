<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-1pjfb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-1pjfb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:card-pay-fill" {...props}></Icon>
