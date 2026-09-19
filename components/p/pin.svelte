<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azllpjbpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azllpjbpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:pin" {...props}></Icon>
