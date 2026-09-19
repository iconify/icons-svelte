<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-0oxbbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-0oxbbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:forward-solid" {...props}></Icon>
