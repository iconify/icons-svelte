<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chyip73rw.css';
import '../../css/i/iyrdw09zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chyip73rw"/><path clip-rule="evenodd" class="iyrdw09zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:broom-line" {...props}></Icon>
