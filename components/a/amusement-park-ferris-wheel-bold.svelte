<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwric7s3u.css';
import '../../css/c/cg9u3_5pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwric7s3u"/><path class="cg9u3_5pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:amusement-park-ferris-wheel-bold" {...props}></Icon>
