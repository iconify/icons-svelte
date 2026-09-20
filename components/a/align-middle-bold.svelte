<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6mhejnyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6mhejnyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:align-middle-bold" {...props}></Icon>
