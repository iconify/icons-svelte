<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5nlnvurm.css';
import '../../css/u/u70j8007s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5nlnvurm"/><path clip-rule="evenodd" class="u70j8007s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lock-keyhole-minimalistic-unlocked-outline" {...props}></Icon>
