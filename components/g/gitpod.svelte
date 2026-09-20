<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-6r57b2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-6r57b2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:gitpod" {...props}></Icon>
