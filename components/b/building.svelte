<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts1w9ibpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ts1w9ibpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:building" {...props}></Icon>
