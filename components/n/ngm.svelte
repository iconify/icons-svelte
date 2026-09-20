<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_h3f3bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w_h3f3bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ngm" {...props}></Icon>
