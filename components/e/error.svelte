<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl-nlrbcy.css';
import '../../css/t/tbhil46-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zl-nlrbcy"/><path class="tbhil46-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:error" {...props}></Icon>
