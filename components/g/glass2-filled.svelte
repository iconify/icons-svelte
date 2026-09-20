<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okacfk43g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okacfk43g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:glass2-filled" {...props}></Icon>
