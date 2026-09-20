<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmu89xj2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cmu89xj2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bbl" {...props}></Icon>
