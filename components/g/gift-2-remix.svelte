<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye19x6bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ye19x6bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:gift-2-remix" {...props}></Icon>
