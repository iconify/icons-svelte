<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evixo2yul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evixo2yul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:reply-all-bulk-round" {...props}></Icon>
