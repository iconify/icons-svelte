<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pico9db3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pico9db3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-error-outline" {...props}></Icon>
