<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbqg4hbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gbqg4hbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:intercom" {...props}></Icon>
