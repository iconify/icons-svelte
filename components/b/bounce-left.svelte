<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q23succzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q23succzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bounce-left" {...props}></Icon>
