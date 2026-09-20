<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyjk4jbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyjk4jbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-94-small" {...props}></Icon>
