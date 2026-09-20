<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdz_qi1ok.css';
import '../../css/m/mwyoejbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdz_qi1ok"/><path clip-rule="evenodd" class="mwyoejbys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lit" {...props}></Icon>
