<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9irnebku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n9irnebku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:phone-vibrate-remix" {...props}></Icon>
