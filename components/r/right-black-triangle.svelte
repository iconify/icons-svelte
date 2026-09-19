<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr2kdabse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="fr2kdabse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:right-black-triangle" {...props}></Icon>
