<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqw6wkb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqw6wkb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:root" {...props}></Icon>
