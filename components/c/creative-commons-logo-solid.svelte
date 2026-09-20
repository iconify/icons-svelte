<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjjp56bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sjjp56bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:creative-commons-logo-solid" {...props}></Icon>
