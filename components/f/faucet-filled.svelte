<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y73pg9rpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y73pg9rpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:faucet-filled" {...props}></Icon>
