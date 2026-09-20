<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp2n7ka7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pp2n7ka7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:flag" {...props}></Icon>
