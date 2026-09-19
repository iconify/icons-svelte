<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leqoybczl.css';
import '../../css/z/zx6m1cc1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="leqoybczl"/><path class="zx6m1cc1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:error-alt" {...props}></Icon>
