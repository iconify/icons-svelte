<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/v/v6my9fadk.css';
import '../../css/t/tmdjm3bnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect transform="rotate(15 6.336 2.19)" class="v6my9fadk"/><rect transform="rotate(15 10.112 8.73)" class="tmdjm3bnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:roblox" {...props}></Icon>
