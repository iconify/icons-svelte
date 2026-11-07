<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpj8th5qt.css';
import '../../css/t/tev9i0bxp.css';
import '../../css/j/j9_7gjbkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpj8th5qt"/><path clip-rule="evenodd" class="tev9i0bxp"/><path class="j9_7gjbkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-wide-bold" {...props}></Icon>
