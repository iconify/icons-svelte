<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3s2ijb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3s2ijb0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-up-right" {...props}></Icon>
