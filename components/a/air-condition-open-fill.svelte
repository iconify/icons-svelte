<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b29sb_hun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b29sb_hun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:air-condition-open-fill" {...props}></Icon>
