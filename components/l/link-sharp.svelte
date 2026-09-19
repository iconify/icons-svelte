<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qflxi5six.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qflxi5six"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:link-sharp" {...props}></Icon>
