<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8ar4sc7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o8ar4sc7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:gift" {...props}></Icon>
