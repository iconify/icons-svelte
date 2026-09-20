<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmennq3iv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pmennq3iv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:align-left-1-remix" {...props}></Icon>
