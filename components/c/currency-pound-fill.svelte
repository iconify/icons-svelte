<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljbnwqb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljbnwqb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-pound-fill" {...props}></Icon>
