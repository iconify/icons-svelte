<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2fxdh14r.css';
import '../../css/e/e_29zdb8m.css';
import '../../css/c/c1r3dshtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h2fxdh14r"/><path class="e_29zdb8m"/><path class="c1r3dshtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:calendar-search-bold" {...props}></Icon>
