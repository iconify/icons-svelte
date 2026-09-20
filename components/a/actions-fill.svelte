<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vflu5yb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vflu5yb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:actions-fill" {...props}></Icon>
