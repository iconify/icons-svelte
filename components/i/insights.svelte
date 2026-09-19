<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfu8axb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pfu8axb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:insights" {...props}></Icon>
