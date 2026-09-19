<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtkxfz27r.css';
import '../../css/x/xz_jktb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtkxfz27r"/><path clip-rule="evenodd" class="xz_jktb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:backspace-outline" {...props}></Icon>
