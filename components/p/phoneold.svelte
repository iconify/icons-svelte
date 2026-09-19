<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2f-5pork.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":960};
const content = `<path class="h2f-5pork"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:phoneold" {...props}></Icon>
