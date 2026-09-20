<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs7ip6b0k.css';
import '../../css/o/od1iqpboh.css';
import '../../css/k/k79q3xboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xs7ip6b0k"/><path class="od1iqpboh"/><circle class="k79q3xboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:image" {...props}></Icon>
