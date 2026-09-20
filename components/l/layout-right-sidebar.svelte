<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpoml5myf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dpoml5myf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:layout-right-sidebar" {...props}></Icon>
