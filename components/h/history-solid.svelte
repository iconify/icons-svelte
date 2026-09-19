<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsv9zc4jv.css';
import '../../css/n/n74bk89qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsv9zc4jv"/><path class="n74bk89qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:history-solid" {...props}></Icon>
