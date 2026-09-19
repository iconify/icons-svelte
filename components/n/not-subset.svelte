<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_d-knbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_d-knbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:not-subset" {...props}></Icon>
