<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwxihp0nr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwxihp0nr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cloud-slash-solid" {...props}></Icon>
