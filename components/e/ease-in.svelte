<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agxbx8tpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agxbx8tpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ease-in" {...props}></Icon>
