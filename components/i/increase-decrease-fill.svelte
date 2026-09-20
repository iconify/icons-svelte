<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gql5y_bcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gql5y_bcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:increase-decrease-fill" {...props}></Icon>
