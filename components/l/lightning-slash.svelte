<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkg302pkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkg302pkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:lightning-slash" {...props}></Icon>
