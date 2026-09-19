<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bob346bis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bob346bis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:push-chevron-up-o" {...props}></Icon>
