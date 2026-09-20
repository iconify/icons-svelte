<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da_3gqzme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="da_3gqzme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:number-three" {...props}></Icon>
