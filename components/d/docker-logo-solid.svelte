<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2c-tw1rf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r2c-tw1rf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:docker-logo-solid" {...props}></Icon>
