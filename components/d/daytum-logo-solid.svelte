<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg3w45bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xg3w45bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:daytum-logo-solid" {...props}></Icon>
