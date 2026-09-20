<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwfssbtso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwfssbtso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-attic" {...props}></Icon>
