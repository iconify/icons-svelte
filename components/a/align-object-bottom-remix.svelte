<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmkvqbc9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jmkvqbc9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:align-object-bottom-remix" {...props}></Icon>
