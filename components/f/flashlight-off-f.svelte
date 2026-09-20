<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hskokab0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-1.5};
const content = `<path class="hskokab0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:flashlight-off-f" {...props}></Icon>
