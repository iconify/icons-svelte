<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9i81zhrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9i81zhrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-lari" {...props}></Icon>
