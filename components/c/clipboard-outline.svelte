<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvuvw1xmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nvuvw1xmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:clipboard-outline" {...props}></Icon>
