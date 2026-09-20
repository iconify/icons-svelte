<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk79hlb8i.css';
import '../../css/n/ncm2tvj9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk79hlb8i"/><path class="ncm2tvj9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:folder-share-bold" {...props}></Icon>
