<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8wpxd25d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8wpxd25d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:question-solid" {...props}></Icon>
