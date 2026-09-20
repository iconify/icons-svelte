<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okody53ea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okody53ea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-j-waves-solid" {...props}></Icon>
