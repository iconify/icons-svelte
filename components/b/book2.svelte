<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0y3sbbpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0y3sbbpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:book2" {...props}></Icon>
