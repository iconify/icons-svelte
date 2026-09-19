<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/goo_yticv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="goo_yticv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:personal-computer" {...props}></Icon>
