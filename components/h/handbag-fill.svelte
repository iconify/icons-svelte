<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o83ojebcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o83ojebcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:handbag-fill" {...props}></Icon>
