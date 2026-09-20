<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr_7g48pa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tr_7g48pa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:keyboard-open" {...props}></Icon>
