<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9sbsvbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":24};
const content = `<path class="s9sbsvbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:night-alt-snow" {...props}></Icon>
