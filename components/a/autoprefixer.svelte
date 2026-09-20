<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvv8gtn1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvv8gtn1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:autoprefixer" {...props}></Icon>
