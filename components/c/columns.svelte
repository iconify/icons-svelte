<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmj2u9wvy.css';
import '../../css/e/e729k1bor.css';
import '../../css/e/e7k_nubxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmj2u9wvy"/><path class="e729k1bor"/><path class="e7k_nubxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:columns" {...props}></Icon>
