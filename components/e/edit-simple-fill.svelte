<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-k_phixn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-k_phixn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:edit-simple-fill" {...props}></Icon>
