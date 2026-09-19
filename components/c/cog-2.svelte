<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtrqn2bnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtrqn2bnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:cog-2" {...props}></Icon>
