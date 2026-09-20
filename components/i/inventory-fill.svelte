<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh12lubuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dh12lubuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:inventory-fill" {...props}></Icon>
