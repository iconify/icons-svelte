<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w36_7vbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w36_7vbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bath-outline" {...props}></Icon>
