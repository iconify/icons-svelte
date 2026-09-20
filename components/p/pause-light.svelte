<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqb36oeds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqb36oeds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:pause-light" {...props}></Icon>
