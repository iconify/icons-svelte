<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-xmtub-r.css';
import '../../css/g/g364_8bya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-xmtub-r"/><path class="g364_8bya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:passkey-fill-24" {...props}></Icon>
