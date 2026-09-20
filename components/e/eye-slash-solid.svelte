<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv2x-ef6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fv2x-ef6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:eye-slash-solid" {...props}></Icon>
