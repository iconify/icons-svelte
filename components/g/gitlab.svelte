<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lipx2eb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lipx2eb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:gitlab" {...props}></Icon>
