<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7okq3bfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="h7okq3bfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-subs" {...props}></Icon>
