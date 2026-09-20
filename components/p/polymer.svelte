<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md3z0jeoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md3z0jeoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:polymer" {...props}></Icon>
