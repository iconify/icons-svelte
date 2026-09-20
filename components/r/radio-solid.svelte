<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_s7-nb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s_s7-nb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:radio-solid" {...props}></Icon>
