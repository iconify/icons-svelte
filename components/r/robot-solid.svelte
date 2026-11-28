<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfguc8bob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfguc8bob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:robot-solid" {...props}></Icon>
