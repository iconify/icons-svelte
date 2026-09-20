<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io3xdv68f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io3xdv68f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ai21labs-jamba" {...props}></Icon>
