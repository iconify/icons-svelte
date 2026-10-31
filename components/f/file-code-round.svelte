<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2o510z7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2o510z7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-code-round" {...props}></Icon>
