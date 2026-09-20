<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6ioh9qho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6ioh9qho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:more-muted-vert-fill" {...props}></Icon>
