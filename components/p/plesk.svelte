<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b797wabdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b797wabdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:plesk" {...props}></Icon>
