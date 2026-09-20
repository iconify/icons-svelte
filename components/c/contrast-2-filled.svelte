<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my3o8r57x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="my3o8r57x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:contrast-2-filled" {...props}></Icon>
