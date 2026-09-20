<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1dymm05g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k1dymm05g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:chevron-left-fill" {...props}></Icon>
