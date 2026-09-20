<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlaksp4ow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rlaksp4ow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cloud-hail" {...props}></Icon>
