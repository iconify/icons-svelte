<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij8shebmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ij8shebmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:cloudsmith-logo-solid" {...props}></Icon>
