<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgnivh30g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgnivh30g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:building-burj-al-arab" {...props}></Icon>
