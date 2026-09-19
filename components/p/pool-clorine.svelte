<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm7w5bbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gm7w5bbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pool-clorine" {...props}></Icon>
