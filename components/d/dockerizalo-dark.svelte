<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjq4rwesi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jjq4rwesi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dockerizalo-dark" {...props}></Icon>
