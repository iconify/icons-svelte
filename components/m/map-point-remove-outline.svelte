<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_i_w5qms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f_i_w5qms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-point-remove-outline" {...props}></Icon>
