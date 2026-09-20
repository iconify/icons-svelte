<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkb-u9edw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkb-u9edw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:feedback-fill" {...props}></Icon>
