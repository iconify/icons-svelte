<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggps2s10o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ggps2s10o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cpu-outline" {...props}></Icon>
