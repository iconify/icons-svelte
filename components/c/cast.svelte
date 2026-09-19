<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lud_oq9-e.css';
import '../../css/f/f3cbn2boa.css';
import '../../css/l/lzg97zbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lud_oq9-e"/><path class="f3cbn2boa"/><path class="lzg97zbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cast" {...props}></Icon>
