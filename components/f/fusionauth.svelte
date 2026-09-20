<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zabn7ccvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zabn7ccvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fusionauth" {...props}></Icon>
