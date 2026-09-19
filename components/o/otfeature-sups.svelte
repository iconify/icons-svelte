<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3ms7hb6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="z3ms7hb6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-sups" {...props}></Icon>
