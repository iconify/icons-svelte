<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmefiacal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmefiacal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:kubernetes" {...props}></Icon>
