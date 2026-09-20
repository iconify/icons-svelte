<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njps49bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njps49bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nodebb" {...props}></Icon>
