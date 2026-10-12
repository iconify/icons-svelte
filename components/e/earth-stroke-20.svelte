<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7mn0ssnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b7mn0ssnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:earth-stroke-20" {...props}></Icon>
