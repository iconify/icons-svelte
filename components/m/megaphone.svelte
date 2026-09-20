<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny0sn3mdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ny0sn3mdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:megaphone" {...props}></Icon>
