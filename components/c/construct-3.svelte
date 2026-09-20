<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh_b1tqjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hh_b1tqjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:construct-3" {...props}></Icon>
