<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3m0kabdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a3m0kabdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:lock-open-solid" {...props}></Icon>
