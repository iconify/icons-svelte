<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-6pfdc6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-6pfdc6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:laptop-upload" {...props}></Icon>
