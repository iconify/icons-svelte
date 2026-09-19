<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt8sy1bpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gt8sy1bpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:chrome-restore" {...props}></Icon>
