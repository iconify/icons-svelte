<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb9ijrb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hb9ijrb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-option" {...props}></Icon>
