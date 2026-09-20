<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo09kqb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vo09kqb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:avalanche-avax-fill" {...props}></Icon>
