<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpimwvprx.css';
import '../../css/d/daxtkab1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpimwvprx"/><path clip-rule="evenodd" class="daxtkab1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:notion-outline" {...props}></Icon>
