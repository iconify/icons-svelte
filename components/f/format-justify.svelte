<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su7aqgb5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="su7aqgb5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:format-justify" {...props}></Icon>
