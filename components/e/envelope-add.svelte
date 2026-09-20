<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kndqyzbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kndqyzbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:envelope-add" {...props}></Icon>
