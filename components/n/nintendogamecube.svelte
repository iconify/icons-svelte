<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd50ifbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yd50ifbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nintendogamecube" {...props}></Icon>
