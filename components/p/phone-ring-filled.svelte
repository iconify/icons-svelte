<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5rchq8iq.css';
import '../../css/j/j5gksabhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5rchq8iq"/><path class="j5gksabhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:phone-ring-filled" {...props}></Icon>
