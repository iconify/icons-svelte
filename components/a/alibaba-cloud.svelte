<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-c6zxvqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-c6zxvqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:alibaba-cloud" {...props}></Icon>
