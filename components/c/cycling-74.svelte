<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or_f8oh-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or_f8oh-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:cycling-74" {...props}></Icon>
