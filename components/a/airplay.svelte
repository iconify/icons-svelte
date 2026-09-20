<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m79pj-b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="m79pj-b6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:airplay" {...props}></Icon>
