<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayqwewbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayqwewbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mcafee" {...props}></Icon>
