<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4m6uvxcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4m6uvxcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:limesurvey" {...props}></Icon>
