<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqflpkaqy.css';
import '../../css/v/vcu56-q6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pqflpkaqy"/><path class="vcu56-q6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:podcast-duotone" {...props}></Icon>
