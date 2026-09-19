<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrez6vbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hrez6vbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:rectangle-group-solid" {...props}></Icon>
