<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzh3pe_2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="uzh3pe_2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-thai" {...props}></Icon>
