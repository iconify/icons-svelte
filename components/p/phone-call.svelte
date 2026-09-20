<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1qdo9jhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1qdo9jhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:phone-call" {...props}></Icon>
