<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9q432bzk.css';
import '../../css/j/jjqv1u30r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x9q432bzk"/><path class="jjqv1u30r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:plain-bold-duotone" {...props}></Icon>
