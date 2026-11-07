<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5u7t3i_i.css';
import '../../css/x/x24uzsf-w.css';
import '../../css/b/bq8-esbzm.css';
import '../../css/o/on0sv8bmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5u7t3i_i"/><path class="x24uzsf-w"/><path class="bq8-esbzm"/><path clip-rule="evenodd" class="on0sv8bmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:masks-outline" {...props}></Icon>
