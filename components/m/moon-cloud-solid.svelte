<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsebaw_qg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bsebaw_qg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:moon-cloud-solid" {...props}></Icon>
