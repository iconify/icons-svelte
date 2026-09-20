<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcs8ekolk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fcs8ekolk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:necktie-solid" {...props}></Icon>
