<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aefll9b6q.css';
import '../../css/b/b0mfz3j4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aefll9b6q"/><path class="b0mfz3j4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:group" {...props}></Icon>
