<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvdre9bdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fvdre9bdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:check-square-fill" {...props}></Icon>
