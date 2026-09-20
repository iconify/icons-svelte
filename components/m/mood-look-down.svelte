<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uubdgd69a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uubdgd69a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mood-look-down" {...props}></Icon>
