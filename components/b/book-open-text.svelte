<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/meiu-pbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="meiu-pbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:book-open-text" {...props}></Icon>
