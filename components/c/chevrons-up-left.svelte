<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgq__9z0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-5};
const content = `<path class="qgq__9z0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevrons-up-left" {...props}></Icon>
