<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvc94accg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvc94accg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:login-solid" {...props}></Icon>
