<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcbwpniha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcbwpniha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:moon-fog-fill" {...props}></Icon>
