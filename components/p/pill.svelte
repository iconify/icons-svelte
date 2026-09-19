<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luulaebmy.css';
import '../../css/a/a7mffllux.css';
import '../../css/f/fk2bfybvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="luulaebmy"/><path class="a7mffllux"/><path class="fk2bfybvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:pill" {...props}></Icon>
