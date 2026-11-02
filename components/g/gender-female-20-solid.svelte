<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8tmqgxvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="n8tmqgxvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:gender-female-20-solid" {...props}></Icon>
