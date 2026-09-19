<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7s9ft_cd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="e7s9ft_cd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:asterisk-fill-12" {...props}></Icon>
