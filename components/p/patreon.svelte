<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2czq3bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2.5};
const content = `<path class="x2czq3bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:patreon" {...props}></Icon>
