<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvuvw1xmg.css';
import '../../css/d/d8pcrprmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nvuvw1xmg"/><path class="d8pcrprmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:clipboard-alt-outline" {...props}></Icon>
