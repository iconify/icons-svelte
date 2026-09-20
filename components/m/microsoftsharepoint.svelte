<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg841gb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zg841gb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:microsoftsharepoint" {...props}></Icon>
