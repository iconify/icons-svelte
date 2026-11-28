<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owsqhqb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owsqhqb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:kettle-check" {...props}></Icon>
