<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da9m5rt6q.css';
import '../../css/e/e3kxkcb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="da9m5rt6q"/><path class="e3kxkcb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:circle-dot-duotone" {...props}></Icon>
