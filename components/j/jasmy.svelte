<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf19libts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pf19libts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:jasmy" {...props}></Icon>
