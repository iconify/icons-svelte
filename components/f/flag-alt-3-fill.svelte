<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3w0jnb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3w0jnb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:flag-alt-3-fill" {...props}></Icon>
