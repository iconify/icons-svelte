<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8ck8wb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8ck8wb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:book-open-check" {...props}></Icon>
