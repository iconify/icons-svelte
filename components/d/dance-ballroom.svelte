<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ervzmi7kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ervzmi7kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dance-ballroom" {...props}></Icon>
