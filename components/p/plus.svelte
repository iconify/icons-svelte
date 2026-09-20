<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eazv3ebih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eazv3ebih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:plus" {...props}></Icon>
