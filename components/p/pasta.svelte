<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh4kocbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lh4kocbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pasta" {...props}></Icon>
