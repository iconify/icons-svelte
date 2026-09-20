<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwi5op4lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwi5op4lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:american-express" {...props}></Icon>
