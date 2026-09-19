<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmkiuqb-h.css';
import '../../css/i/icpcz1bju.css';
import '../../css/g/gah67z6_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mmkiuqb-h"/><circle class="icpcz1bju"/><path class="gah67z6_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:event-change" {...props}></Icon>
