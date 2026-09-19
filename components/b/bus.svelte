<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf2zg36gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uf2zg36gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:bus" {...props}></Icon>
