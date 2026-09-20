<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdkgnbbwr.css';
import '../../css/l/lcfo21bnz.css';
import '../../css/k/kfdgnyb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdkgnbbwr"/><path clip-rule="evenodd" class="lcfo21bnz"/><path clip-rule="evenodd" class="kfdgnyb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:layers-fill" {...props}></Icon>
