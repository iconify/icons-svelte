<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awp4qobzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="awp4qobzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:ati-logo-solid" {...props}></Icon>
