<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cizcas08r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cizcas08r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-fact-line" {...props}></Icon>
