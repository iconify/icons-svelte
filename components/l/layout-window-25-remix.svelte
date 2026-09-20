<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnv1cu90a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vnv1cu90a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:layout-window-25-remix" {...props}></Icon>
