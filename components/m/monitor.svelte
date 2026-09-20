<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4wt7sbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4wt7sbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:monitor" {...props}></Icon>
