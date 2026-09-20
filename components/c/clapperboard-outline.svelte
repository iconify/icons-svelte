<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcj0pibjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tcj0pibjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clapperboard-outline" {...props}></Icon>
