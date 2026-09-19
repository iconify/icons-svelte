<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1gahrb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path clip-rule="evenodd" class="l1gahrb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:remote-explorer" {...props}></Icon>
