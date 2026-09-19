<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn4o2qi9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nn4o2qi9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:pin-outline" {...props}></Icon>
