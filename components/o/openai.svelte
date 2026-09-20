<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r07fs7qse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r07fs7qse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:openai" {...props}></Icon>
