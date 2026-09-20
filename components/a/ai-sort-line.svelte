<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b55gmjb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b55gmjb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-sort-line" {...props}></Icon>
