<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snrjwhbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snrjwhbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:heading-3" {...props}></Icon>
