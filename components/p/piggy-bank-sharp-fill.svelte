<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urfk5jbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urfk5jbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:piggy-bank-sharp-fill" {...props}></Icon>
