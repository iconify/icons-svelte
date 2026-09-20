<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_kb5ab6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_kb5ab6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:notist" {...props}></Icon>
