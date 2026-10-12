<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9scvyboa.css';
import '../../css/y/yyqev4b5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9scvyboa"/><path class="yyqev4b5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:folder-root-filled" {...props}></Icon>
