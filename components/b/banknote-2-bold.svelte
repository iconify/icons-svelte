<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq8x0oj0m.css';
import '../../css/g/gi40zsmhu.css';
import '../../css/a/a1okgrd2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq8x0oj0m"/><path class="gi40zsmhu"/><path clip-rule="evenodd" class="a1okgrd2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:banknote-2-bold" {...props}></Icon>
