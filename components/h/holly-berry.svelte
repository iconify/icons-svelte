<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz-e9hbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="fz-e9hbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:holly-berry" {...props}></Icon>
