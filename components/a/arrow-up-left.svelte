<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqb21eg5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqb21eg5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:arrow-up-left" {...props}></Icon>
