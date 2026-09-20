<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq--4rb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="nq--4rb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:dollar" {...props}></Icon>
