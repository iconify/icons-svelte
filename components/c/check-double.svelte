<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_2c1bbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_2c1bbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:check-double" {...props}></Icon>
