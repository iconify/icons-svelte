<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph9ekmbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ph9ekmbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ear-nose-throat" {...props}></Icon>
