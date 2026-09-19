<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmf71jbnp.css';
import '../../css/d/d6aw1qt_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmf71jbnp"/><path clip-rule="evenodd" class="d6aw1qt_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:confirmations-5-filled" {...props}></Icon>
