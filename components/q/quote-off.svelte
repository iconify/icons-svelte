<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzab_7yls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzab_7yls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:quote-off" {...props}></Icon>
