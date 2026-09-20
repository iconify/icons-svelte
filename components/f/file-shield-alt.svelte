<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1p4y9t4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1p4y9t4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:file-shield-alt" {...props}></Icon>
