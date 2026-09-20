<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk1o3d6dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk1o3d6dn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:amazon" {...props}></Icon>
