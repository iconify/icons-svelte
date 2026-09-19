<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3t9q1bdx.css';
import '../../css/b/bgdvneanc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y3t9q1bdx"/><path class="bgdvneanc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:credit-card-front" {...props}></Icon>
