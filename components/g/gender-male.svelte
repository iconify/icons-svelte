<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9tzvybim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9tzvybim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:gender-male" {...props}></Icon>
