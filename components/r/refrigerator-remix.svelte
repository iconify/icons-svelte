<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti64bp60p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ti64bp60p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:refrigerator-remix" {...props}></Icon>
