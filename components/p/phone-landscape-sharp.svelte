<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/giyl09eny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="giyl09eny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:phone-landscape-sharp" {...props}></Icon>
