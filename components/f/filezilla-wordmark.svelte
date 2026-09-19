<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr-3jmbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vr-3jmbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:filezilla-wordmark" {...props}></Icon>
