<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5j6r5bas.css';
import '../../css/k/kj3cr3nbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5j6r5bas"/><path class="kj3cr3nbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:credit-card-front" {...props}></Icon>
