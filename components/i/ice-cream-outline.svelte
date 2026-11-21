<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bem5i2brp.css';
import '../../css/q/qjzeox4ix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bem5i2brp"/><path class="qjzeox4ix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ice-cream-outline" {...props}></Icon>
