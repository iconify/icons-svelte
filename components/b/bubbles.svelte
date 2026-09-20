<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k99wge7hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="k99wge7hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:bubbles" {...props}></Icon>
