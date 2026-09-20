<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv9bc4j-a.css';
import '../../css/z/zmmw0rbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kv9bc4j-a"/><path class="zmmw0rbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:boa" {...props}></Icon>
