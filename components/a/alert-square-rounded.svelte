<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8fv07biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8fv07biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:alert-square-rounded" {...props}></Icon>
