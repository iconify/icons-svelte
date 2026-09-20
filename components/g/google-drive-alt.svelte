<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9ot2f44q.css';
import '../../css/i/it9p5abzo.css';
import '../../css/n/n0frhibvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9ot2f44q"/><path class="it9p5abzo"/><path class="n0frhibvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:google-drive-alt" {...props}></Icon>
