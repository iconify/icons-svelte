<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skbbg-s7m.css';
import '../../css/o/o4ad8gbrb.css';
import '../../css/f/fnw06pb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skbbg-s7m"/><path clip-rule="evenodd" class="o4ad8gbrb"/><path class="fnw06pb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-move-light" {...props}></Icon>
