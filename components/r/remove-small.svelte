<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxt91fbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="uxt91fbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:remove-small" {...props}></Icon>
