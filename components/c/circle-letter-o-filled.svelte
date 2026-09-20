<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q86lr8bry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q86lr8bry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-letter-o-filled" {...props}></Icon>
