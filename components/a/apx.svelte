<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/niq5zhxqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="niq5zhxqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:apx" {...props}></Icon>
