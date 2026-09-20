<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqzupl6gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqzupl6gc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:controller-circle-down" {...props}></Icon>
