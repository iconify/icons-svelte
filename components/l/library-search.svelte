<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fytmvbx1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fytmvbx1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:library-search" {...props}></Icon>
