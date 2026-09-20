<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs-8h9bie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xs-8h9bie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:envato" {...props}></Icon>
