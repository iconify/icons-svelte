<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqzxq_bgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path clip-rule="evenodd" class="bqzxq_bgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bolt-2" {...props}></Icon>
