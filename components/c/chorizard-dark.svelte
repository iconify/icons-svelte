<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tua1clvxp.css';
import '../../css/i/imad5bjrh.css';
import '../../css/n/ngse4mb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tua1clvxp"/><path class="imad5bjrh"/><path class="ngse4mb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chorizard-dark" {...props}></Icon>
