<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp37ko-fv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hp37ko-fv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:nose-24px" {...props}></Icon>
