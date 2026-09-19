<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c18lasbzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="c18lasbzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:black-sun-with-rays" {...props}></Icon>
