<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs06k9b7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gs06k9b7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:hard-hat-solid" {...props}></Icon>
