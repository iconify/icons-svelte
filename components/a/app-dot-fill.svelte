<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpg27mbvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpg27mbvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:app-dot-fill" {...props}></Icon>
