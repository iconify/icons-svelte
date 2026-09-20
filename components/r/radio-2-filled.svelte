<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkb0jcelk.css';
import '../../css/b/breyi0bij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkb0jcelk"/><path class="breyi0bij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:radio-2-filled" {...props}></Icon>
