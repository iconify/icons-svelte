<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euguvfp6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="euguvfp6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:leaf-2-fill" {...props}></Icon>
