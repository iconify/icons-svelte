<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8q33qb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m8q33qb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:asymmetrik" {...props}></Icon>
