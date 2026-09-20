<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muy2xg7rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="muy2xg7rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:database-server-2" {...props}></Icon>
