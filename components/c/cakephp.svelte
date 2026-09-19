<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky5natb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ky5natb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:cakephp" {...props}></Icon>
