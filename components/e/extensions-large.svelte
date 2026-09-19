<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si18as_vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="si18as_vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:extensions-large" {...props}></Icon>
