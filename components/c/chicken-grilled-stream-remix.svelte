<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7fvnobse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z7fvnobse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:chicken-grilled-stream-remix" {...props}></Icon>
