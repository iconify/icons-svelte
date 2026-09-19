<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9q15b9rp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j9q15b9rp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:fitbit" {...props}></Icon>
