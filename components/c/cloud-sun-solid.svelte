<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csipk0bxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csipk0bxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cloud-sun-solid" {...props}></Icon>
