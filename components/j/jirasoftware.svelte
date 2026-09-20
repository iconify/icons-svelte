<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lskd2sbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lskd2sbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:jirasoftware" {...props}></Icon>
