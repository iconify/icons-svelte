<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okle9ebwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okle9ebwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:man" {...props}></Icon>
