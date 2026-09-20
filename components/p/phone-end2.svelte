<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g91dgxblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g91dgxblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:phone-end2" {...props}></Icon>
