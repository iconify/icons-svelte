<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bezyg0w5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bezyg0w5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:optical-character-recognition" {...props}></Icon>
