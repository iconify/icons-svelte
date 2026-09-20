<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3qg_u9su.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3qg_u9su"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:double-arrow-right-duotone" {...props}></Icon>
