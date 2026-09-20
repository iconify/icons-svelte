<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmwx09b0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tmwx09b0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fireworks" {...props}></Icon>
