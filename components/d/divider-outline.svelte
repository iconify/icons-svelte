<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho_vuac_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ho_vuac_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:divider-outline" {...props}></Icon>
