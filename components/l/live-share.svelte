<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6xyl5_4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path class="b6xyl5_4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:live-share" {...props}></Icon>
