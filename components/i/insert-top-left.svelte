<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nokox8bjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nokox8bjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:insert-top-left" {...props}></Icon>
