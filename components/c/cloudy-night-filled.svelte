<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mat9etbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mat9etbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:cloudy-night-filled" {...props}></Icon>
