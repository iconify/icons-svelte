<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1yu04b5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k1yu04b5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:iris-scan-solid" {...props}></Icon>
