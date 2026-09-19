<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eatr3hojb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eatr3hojb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cylinder" {...props}></Icon>
