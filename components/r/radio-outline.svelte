<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mew9r2bpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mew9r2bpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:radio-outline" {...props}></Icon>
