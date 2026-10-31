<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh2693boa.css';
import '../../css/v/vlyhmq5ak.css';
import '../../css/g/gkjkb4bue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="lh2693boa"/><path class="vlyhmq5ak"/><path class="gkjkb4bue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:jamaica" {...props}></Icon>
