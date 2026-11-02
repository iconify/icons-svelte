<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjv1u1-hz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjv1u1-hz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:american-express-fill" {...props}></Icon>
