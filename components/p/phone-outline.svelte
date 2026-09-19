<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps7l495qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ps7l495qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:phone-outline" {...props}></Icon>
