<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-01g-evr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v-01g-evr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:earth-2-solid" {...props}></Icon>
