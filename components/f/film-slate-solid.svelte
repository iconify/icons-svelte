<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcw95gb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zcw95gb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:film-slate-solid" {...props}></Icon>
