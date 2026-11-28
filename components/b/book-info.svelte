<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6-p1fb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6-p1fb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:book-info" {...props}></Icon>
