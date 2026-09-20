<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2ehimbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2ehimbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate-color:rating-star-three" {...props}></Icon>
