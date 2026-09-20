<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no27z1b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="no27z1b-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:letter-g" {...props}></Icon>
