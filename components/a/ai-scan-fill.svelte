<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eub1h9d7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eub1h9d7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-scan-fill" {...props}></Icon>
