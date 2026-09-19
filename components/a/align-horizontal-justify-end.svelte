<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3kdx2nau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3kdx2nau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:align-horizontal-justify-end" {...props}></Icon>
