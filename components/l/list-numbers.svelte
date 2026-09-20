<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glxfj3qif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glxfj3qif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:list-numbers" {...props}></Icon>
