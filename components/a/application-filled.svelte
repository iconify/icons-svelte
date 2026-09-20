<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud5o94vem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ud5o94vem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:application-filled" {...props}></Icon>
