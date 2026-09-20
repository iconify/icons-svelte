<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otyeiu5va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otyeiu5va"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:package-solid" {...props}></Icon>
