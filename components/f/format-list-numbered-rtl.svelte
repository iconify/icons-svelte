<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-00mr7rz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-00mr7rz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-list-numbered-rtl" {...props}></Icon>
