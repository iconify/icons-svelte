<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu247bctc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bu247bctc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:grid6" {...props}></Icon>
