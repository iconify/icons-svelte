<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrn42abvu.css';
import '../../css/f/f-ksdqydc.css';
import '../../css/c/c7gfsbb7m.css';
import '../../css/s/spxynnb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrn42abvu"/><circle class="f-ksdqydc"/><circle class="c7gfsbb7m"/><circle class="spxynnb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:chat-alt-3-light" {...props}></Icon>
