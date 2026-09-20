<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psgtoi7vi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psgtoi7vi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ray" {...props}></Icon>
