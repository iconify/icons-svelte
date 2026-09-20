<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht8hvn-4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ht8hvn-4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:external-link-fill" {...props}></Icon>
