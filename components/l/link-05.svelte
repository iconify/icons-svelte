<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwi3tdbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwi3tdbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:link-05" {...props}></Icon>
