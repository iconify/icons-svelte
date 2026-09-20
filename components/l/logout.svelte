<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f52y9dbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f52y9dbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:logout" {...props}></Icon>
