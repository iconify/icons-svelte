<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hiw02y_uk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hiw02y_uk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:letter-z" {...props}></Icon>
