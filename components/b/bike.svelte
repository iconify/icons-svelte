<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkrps6bdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tkrps6bdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bike" {...props}></Icon>
