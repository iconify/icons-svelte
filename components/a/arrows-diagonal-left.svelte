<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktt2-ebbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktt2-ebbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:arrows-diagonal-left" {...props}></Icon>
