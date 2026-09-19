<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obm7hd71g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="obm7hd71g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-zero-small" {...props}></Icon>
