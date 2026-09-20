<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbq_a9bna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kbq_a9bna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:fandom-logo-2-block" {...props}></Icon>
