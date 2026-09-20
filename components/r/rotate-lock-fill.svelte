<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4zw4yxvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4zw4yxvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:rotate-lock-fill" {...props}></Icon>
