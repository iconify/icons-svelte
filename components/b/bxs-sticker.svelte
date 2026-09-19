<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui62x8afp.css';
import '../../css/z/za24chbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ui62x8afp"/><path class="za24chbrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-sticker" {...props}></Icon>
