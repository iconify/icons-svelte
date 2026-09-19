<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgobqvysn.css';
import '../../css/f/fzc4cyr3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgobqvysn"/><path class="fzc4cyr3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:api-outlined" {...props}></Icon>
