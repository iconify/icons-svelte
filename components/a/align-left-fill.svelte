<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m66ceobye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m66ceobye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-left-fill" {...props}></Icon>
