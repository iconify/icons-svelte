<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj_-u5bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mj_-u5bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:arrow-up-duotone" {...props}></Icon>
