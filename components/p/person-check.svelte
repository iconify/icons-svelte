<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj47757af.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sj47757af"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:person-check" {...props}></Icon>
