<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snne3jg4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snne3jg4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:arrow-button-up-bold" {...props}></Icon>
