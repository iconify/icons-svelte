<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w69pzst6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w69pzst6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pypy" {...props}></Icon>
