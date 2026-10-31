<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0p3ldb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0p3ldb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-minus-round" {...props}></Icon>
