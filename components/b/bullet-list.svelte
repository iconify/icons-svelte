<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui9se-bue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ui9se-bue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:bullet-list" {...props}></Icon>
