<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyqnu2ioa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eyqnu2ioa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:eight-solid" {...props}></Icon>
