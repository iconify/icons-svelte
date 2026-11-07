<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7dkp0b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g7dkp0b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:eye-closed-outline" {...props}></Icon>
