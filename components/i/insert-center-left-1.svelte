<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr9vhtbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="mr9vhtbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:insert-center-left-1" {...props}></Icon>
