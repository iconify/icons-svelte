<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa1q5gb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aa1q5gb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hypermind-dark" {...props}></Icon>
