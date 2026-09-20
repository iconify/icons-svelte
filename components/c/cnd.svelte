<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzqt9rbax.css';
import '../../css/p/pm0grmbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zzqt9rbax"/><path class="pm0grmbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cnd" {...props}></Icon>
