<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1ot5pd2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c1ot5pd2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:caret-right-outline" {...props}></Icon>
