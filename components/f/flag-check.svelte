<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvntf3bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvntf3bap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:flag-check" {...props}></Icon>
