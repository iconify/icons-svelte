<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf4fnjzzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lf4fnjzzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ghost-3" {...props}></Icon>
