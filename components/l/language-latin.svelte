<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecsl_f_4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ecsl_f_4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-latin" {...props}></Icon>
