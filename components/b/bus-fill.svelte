<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8ywu5bta.css';
import '../../css/s/s776ws_jb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8ywu5bta"/><path clip-rule="evenodd" class="s776ws_jb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:bus-fill" {...props}></Icon>
