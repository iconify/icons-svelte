<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2m2lgoyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2m2lgoyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panels-top-left-sharp-fill" {...props}></Icon>
