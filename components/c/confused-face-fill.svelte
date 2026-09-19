<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-28ubbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n-28ubbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:confused-face-fill" {...props}></Icon>
