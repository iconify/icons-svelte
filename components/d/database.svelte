<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh9h2u3sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nh9h2u3sn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:database" {...props}></Icon>
