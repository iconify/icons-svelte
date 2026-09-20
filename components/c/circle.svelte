<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzsfz8ozm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzsfz8ozm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:circle" {...props}></Icon>
