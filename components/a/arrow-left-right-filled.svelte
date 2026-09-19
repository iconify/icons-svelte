<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk7yzqbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk7yzqbym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-left-right-filled" {...props}></Icon>
