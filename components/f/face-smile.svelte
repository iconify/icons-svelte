<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyoi2_bhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyoi2_bhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:face-smile" {...props}></Icon>
