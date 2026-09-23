<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceduwrv8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ceduwrv8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:eject-sharp" {...props}></Icon>
