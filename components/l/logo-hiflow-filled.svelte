<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prk4vvnlx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prk4vvnlx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-hiflow-filled" {...props}></Icon>
