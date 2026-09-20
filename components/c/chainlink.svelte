<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agfs7ab5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agfs7ab5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:chainlink" {...props}></Icon>
