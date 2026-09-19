<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/liblnjhws.css';
import '../../css/f/fjtbb1h3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="liblnjhws"/><path class="fjtbb1h3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:dns" {...props}></Icon>
