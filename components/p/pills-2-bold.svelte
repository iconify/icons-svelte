<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbjz5kw6b.css';
import '../../css/m/mly957b2e.css';
import '../../css/m/mjkz43bbw.css';
import '../../css/b/b8h19izcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbjz5kw6b"/><path class="mly957b2e"/><path class="mjkz43bbw"/><path class="b8h19izcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pills-2-bold" {...props}></Icon>
