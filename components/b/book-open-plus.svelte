<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmzuekb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmzuekb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:book-open-plus" {...props}></Icon>
