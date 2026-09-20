<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3quegb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a3quegb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:phone-vibrate-solid" {...props}></Icon>
