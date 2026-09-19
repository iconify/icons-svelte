<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar2nsacbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar2nsacbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:cloud-off" {...props}></Icon>
