<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0wct_3jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0wct_3jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:gogdotcom" {...props}></Icon>
